# División en componentes de la app

## ¿Qué se pretende implementar como una actividad?

* Inicio de sesión (LoginActivity)
* Registro en la aplicación (SignupActivity)
* Subir contenido (PostActivity)
* Reconocimiento de música
* Núcleo de la aplicación (MainActivity)

## ¿Qué se va a implementar como un servicio?

* Publicación de contenido
* Actualización de información del perfil
* Procesado del _feed_

## ¿Qué se va a implementar con fragments?

El resto de elementos de la barra de navegación:
* Home - _Posts_
* Home - _Daily posts_
* Home - _Ver perfil_
* Home - _Editar perfil_
* Búsqueda
* Notificaciones
* Mapa

## ¿Quién lanza a quién y quién hace uso de los fragments o los servicios?

La actividad de inicio de sesión lanza la de registro y viceversa. Estas dos actividades lanzan a su vez, la actividad principal, la cual es el núcleo de la aplicación. Podemos navegar entre los distintos fragments y acceder a la actividad para publicar contenido a través de la barra de navegación. Además, la actividad principal contiene un botón en todo momento para llamar a la funcionalidad de reconocimiento de música.

# Mockups de pantallas grandes o tablets

Podemos ver todos los mockups de la aplicación en: [SoundShare | Marvel](https://marvelapp.com/prototype/a4cj23d).

***

Esta entrega se puede encontrar en la release: [Entrega 06: Componentes y fragmentos](https://github.com/ikergcalvino/SoundShare/releases/tag/v0.2).