---
title:  "Los puertos FXO no desconectan"
hidden: true
comments: true
date: 2017-04-14 14:25:00  
categories: #[Telefonía, Guías]
tags: #[FXO, Configuración, Guía]
keywords: [CISCO FXO disconnect, hangup detection, detección de colgado de una llamada]
excerpt: Las FXO no cortan las llamadas. Al responder escucho silencio. Todas las líneas de cobre me dan ocupado. Son frases que nos pueden dar algún dolor de cabeza. Hay sitios que mi configuración funciona bien, pero otros en que no. ¿Cómo podemos solucionar este inconveniente?
---
![](/images/posts/...)

Esta vez quiero compartir la solución a un problema que se volvió común y que además es consultado en diversos foros de voz sobre IP. Aunque van a ver que los ejemplos y solución se basan en dispositivos CISCO, esto es porque son los que tengo a mi alcance.

## En la empresa, pero también en la casa

Mi idea es que se entienda cuál es el problema y su solución, dejando el detalle de configuración a cada administrador según el equipamiento o software que utiliza. Así que ya sea si tienes una central Asterisk corriendo en el PC de tu casa, o si te encuentras inmerso en una gran plataforma de telefonía IP en tu empresa, puede que encuentres cómo lograr que tus llamadas urbanas no se *cuelguen*.

## ¿Por qué sucede?
