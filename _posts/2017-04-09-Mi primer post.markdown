---
title:  "¡Mi primer post con Jekyll!"
comments: true
date:   2017-04-09 17:00:00
categories: [Programación]
tags: [Jekyll]
keywords: [Jekyll, Blog, GitHub-pages, Estático, Hosting]
excerpt: Quería escribir un blog, pero <strong>no solo el contenido</strong>. No quería caer en servicios que te dejan todo listo, son dueños de toda tu informaicón y pierdes todo si dejan de existir, pero quería que sea gratis. Aquí les cuento <strong>cómo lo hice</strong>.
---
Primero quiero agradecer a [Gervasio Marchand](https://g3rv4.com/), programador, ingeniero, nerd y amigo. No necesariamente en ese orden. :P Él despertó mi interés en este emprendimiento y algunos de sus posts fueron de gran ayuda.

Aquí va el resumen de cómo hice este blog.

## ¿Qué buscaba?

_Cortito y al pie:_ un blog del que tuviera el control.

Esto implica que tengo el código fuente, lo modifico a gusto, no tengo las restricciones que imponen los servicios de blog gratuitos, tengo una copia local de todo el sitio y no importa si el lugar de hosting deja de existir.

## Búsqueda de un dominio.

Ya tengo un dominio pago: [www.seveloquedigo.com](http://www.seveloquedigo.com) (dedicado al humor) y no quería pagar dos. En un futuro, si todo va bien, veré esta posibilidad, pero por ahora soy mi único lector. jaja.

Si quieren tener una idea, cuesta 14 USD al año, en realidad no es un servicio caro.

En este punto debo agradecer a los dominios gratuitos. La idea no es profundizar en esto, pero aquí hay algunos puntos a tener en cuenta:
* Solo permiten registros de un año de duración
* La opción de renovación, aunque es gratuita puede realizarse solo desde las dos semanas anteriores a su vencimiento
* Seguramente no seas dueño del dominio
* No son extensiones conocidas como (.com .es . net) y cada vez más gente conoce que ha sido un registro gratuito, afectando la imagen del producto que quieres compartir.

Luego de un rato de búsqueda, me decidí por el dominio tk, ofrecido por el servicio [freenom](http://www.freenom.com/es/freeandpaiddomains.html)

## Servidor de nombre DNS

Freenom, adicionalmente ofrece un servicio gratuito de servidor DNS. Esto ayudó a que optara por esta empresa, ya que otras ofrecen una simple redirección.

## ¿Qué pasa con el hosting?

Un hosting cuesta alrededor de 70 USD al año. Así que seguí investigando.

Encontré que [GitHub](https://github.com/), el ya conocido sitio para desarrolladores, ahora ofrece un servicio llamado [Github-Pages](https://pages.github.com/) que permite utilizar uno de tus repositorios como Website (se traduce en _hosting gratuito_).

Esto es una genialidad, tu sitio web tiene a su disposición todas las herramientas ofrecidas para tus códigos: control de versiones, merge, sincronización local, pull, push, etc.

En [Github-Pages](https://pages.github.com/) se encuentran los pasos para crear un repositorio apto para usarlo de sitio web. Utilicé `mauroba.github.io` como nombre del repositorio porque me da la posibilidad de que ese mismo se convierta en la url raíz. En una primera instancia utilicé el nombre `blog` pero resultó que para acceder al mismo debía usar la url `mauroba.github.io/blog`.

En la configuración del repositorio encontré la posibilidad de utilizar el dominio que compré (esto además requirió que cree un CNAME en el servidor DNS proporcionado por Freenom).

Al finalizar esta etapa, si elijes un template para tu sitio, ya puedes acceder al mismo.

Pero no basta con un hosting, ¿Cómo diseñaría y mantendría un blog sobre github-pages? Yo soy un futuro ingeniero eléctrico con una pasión escondida hacia la programación, pero no soy realmente un desarrollador.

Pero bueno, en la web de GitHub te indican que para blogs se puede utilizar [Jekyll](https://jekyllrb.com), y en la web de Jekyll indica que trabaja sobre GitHub...

Así que seguí por ahí.

## ¿Jekyll?

Es un _generador estático diseñado para blogs_. ¿Qué es lo que me gustó más de él? La posibilidad de sentirme en la matrix.

Suena gracioso pero es verdad. No es para cualquier usuario final, los post se escriben en consola o en un editor de textos. Te olvidas de los frustrantes formatos automáticos que aparecen y desaparecen cuando quieren en los servicios de blogs online. Es un poco como escribir en Latex.

Así que me decidí por Jekyll. Busqué un template entre los muchos que hay en la web y lo cloné en mi repositorio de GitHub (adiós al sitio por defecto que tenía en él).

### Instalación de Jekyll

En cuanto a la instalación en Windows (sí, uso Windows) la pude hacer sin menores contratiempos, pero no voy a decir que _salió con fritas_.

Los pasos de instalación son:
1. Instalar la última versión de ruby, desde el sitio oficial
2. Instalar bundler: `gem install bundler`
3. Instalar jekyll: `gem install jekyll`

Lo cierto es que tuve algunos contratiempos, que se solucionaron con alguna búsqueda en la web.

### Uso de Jekyll

Ya con el template de Jekyll listo en el repositorio de GitHub, fue fácil instalar el _GitHub desktop_ para obtener una carpeta sincronizada localmente del blog.

Luego de hecho esto, instalé [Atom](https://atom.io/) para editar los archivos de código (muuuy reocmendable) y bastó con posicionarme en la carpeta local usando el command prompt para iniciar el servicio de jekyll:
`bundle exec jekyll serve --watch`

Esto corre un servicio que mostrará el blog en la url `localhost:4000`, permitiendo ver los cambios en tiempo real y así luego sincronizarlos con GitHub al final. La opción `--watch` permite que el servicio esté viendo constantemente si hay cambios en los archivos y así mostrarlos sin tener que reiniciarlo.

## Y así fue

¡Y llegamos al final! A modificar el código del sitio a gusto y a crear entradas para el blog.

¡Nos leemos en la próxima!
